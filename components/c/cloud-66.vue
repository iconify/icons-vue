<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjqachngk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjqachngk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cloud-66" /></template>
