<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs06k9b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs06k9b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hard-hat-solid" /></template>
