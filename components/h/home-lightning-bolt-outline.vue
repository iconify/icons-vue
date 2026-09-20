<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnn6g-38f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnn6g-38f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-lightning-bolt-outline" /></template>
