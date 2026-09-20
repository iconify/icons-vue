<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_5nzzr0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_5nzzr0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:file" /></template>
