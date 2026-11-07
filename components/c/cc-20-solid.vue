<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9f2r2p1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w9f2r2p1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cc-20-solid" /></template>
