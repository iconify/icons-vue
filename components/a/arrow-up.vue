<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afwu872mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afwu872mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-up" /></template>
