<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2yxpxb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s2yxpxb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:envelope-open-20-solid" /></template>
