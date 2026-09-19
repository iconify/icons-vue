<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aitpvr66y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":328,"height":512};
const content = `<path class="aitpvr66y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:cutlery" /></template>
