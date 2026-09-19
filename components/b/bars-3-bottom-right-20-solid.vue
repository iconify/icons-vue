<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rok2wacqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rok2wacqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3-bottom-right-20-solid" /></template>
