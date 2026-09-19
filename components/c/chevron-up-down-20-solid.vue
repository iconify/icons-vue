<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4aw28bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m4aw28bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-up-down-20-solid" /></template>
