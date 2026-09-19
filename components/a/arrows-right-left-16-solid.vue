<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0xrvnbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q0xrvnbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrows-right-left-16-solid" /></template>
