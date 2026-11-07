<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7_w9-itf.css';
import '../../css/z/zn77u3fhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7_w9-itf"/><path class="zn77u3fhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forbidden-circle-bold" /></template>
