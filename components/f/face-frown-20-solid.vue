<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evxv_sbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="evxv_sbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:face-frown-20-solid" /></template>
