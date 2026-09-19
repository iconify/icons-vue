<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxvj8wsrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="oxvj8wsrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:camera-20-solid" /></template>
