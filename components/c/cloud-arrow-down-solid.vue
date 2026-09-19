<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj-j1uuvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nj-j1uuvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cloud-arrow-down-solid" /></template>
