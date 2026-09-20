<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4kelcc9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l4kelcc9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bed" /></template>
