<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc3gm6bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pc3gm6bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-right" /></template>
