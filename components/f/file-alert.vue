<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zww523woh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zww523woh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-alert" /></template>
