<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmbmvfb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmbmvfb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:arrow-right-down" /></template>
