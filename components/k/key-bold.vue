<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiz_subtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tiz_subtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-bold" /></template>
