<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2woclr0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p2woclr0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:electron" /></template>
