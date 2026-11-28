<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anu2djb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anu2djb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:droplet-plus" /></template>
