<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7hd_4b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u7hd_4b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:beaker-20-solid" /></template>
