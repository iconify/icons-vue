<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id-pioxhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id-pioxhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dollar-sign" /></template>
