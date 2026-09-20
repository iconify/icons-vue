<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8tex2cnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n8tex2cnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:information" /></template>
