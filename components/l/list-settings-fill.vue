<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd7vs07pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd7vs07pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:list-settings-fill" /></template>
