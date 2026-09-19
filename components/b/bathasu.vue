<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xspxmgd4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xspxmgd4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:bathasu" /></template>
