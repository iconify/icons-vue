<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spw5_r41r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="spw5_r41r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:code-bracket-20-solid" /></template>
