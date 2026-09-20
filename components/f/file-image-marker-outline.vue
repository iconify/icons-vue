<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snypjj0it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snypjj0it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-image-marker-outline" /></template>
