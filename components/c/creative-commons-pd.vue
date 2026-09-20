<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxpm_3bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxpm_3bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:creative-commons-pd" /></template>
