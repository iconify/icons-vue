<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7lb87rwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7lb87rwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:do-not-disturb" /></template>
