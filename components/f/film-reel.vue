<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmi07ebkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmi07ebkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-reel" /></template>
