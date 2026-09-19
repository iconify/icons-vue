<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_js-l3oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_js-l3oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:edit" /></template>
