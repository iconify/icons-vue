<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur8ru8b9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur8ru8b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:apachenifi" /></template>
