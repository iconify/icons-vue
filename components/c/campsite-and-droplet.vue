<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn_ek_m6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kn_ek_m6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-and-droplet" /></template>
