<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he5vvvb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he5vvvb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forbidden-circle-filled" /></template>
