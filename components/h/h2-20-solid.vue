<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvrww6bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wvrww6bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:h2-20-solid" /></template>
