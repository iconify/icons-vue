<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq1eo_bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq1eo_bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bitcomet" /></template>
