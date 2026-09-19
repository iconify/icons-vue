<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6c6d7t2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p6c6d7t2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:lua" /></template>
