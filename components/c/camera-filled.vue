<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_ocu_pkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p_ocu_pkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:camera-filled" /></template>
