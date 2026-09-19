<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk_2qoknp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kk_2qoknp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:archive-box-arrow-down" /></template>
