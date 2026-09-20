<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih6-fu92y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih6-fu92y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-network-off-outline" /></template>
