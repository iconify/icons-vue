<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr5d99b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wr5d99b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-left-circle-solid" /></template>
