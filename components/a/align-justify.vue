<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbd8sc2no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbd8sc2no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-justify" /></template>
