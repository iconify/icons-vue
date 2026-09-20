<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk0v-q3wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sk0v-q3wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-waterdrop-outline" /></template>
