<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suw-znhgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suw-znhgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-up-solid" /></template>
