<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgl53ia8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgl53ia8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:angles-up" /></template>
