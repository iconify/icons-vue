<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbc0g8wzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cbc0g8wzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-right-16-solid" /></template>
