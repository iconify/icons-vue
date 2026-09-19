<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrsh7gb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="xrsh7gb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:archive" /></template>
