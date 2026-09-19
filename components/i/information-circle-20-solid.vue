<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-hejqbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="r-hejqbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:information-circle-20-solid" /></template>
