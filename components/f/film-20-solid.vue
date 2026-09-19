<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lup-_0bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lup-_0bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:film-20-solid" /></template>
