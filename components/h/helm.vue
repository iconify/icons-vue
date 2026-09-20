<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txfurg8nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txfurg8nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:helm" /></template>
