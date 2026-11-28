<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho7un-mez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho7un-mez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-heart" /></template>
