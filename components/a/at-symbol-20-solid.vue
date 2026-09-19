<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_jqjh0hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k_jqjh0hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:at-symbol-20-solid" /></template>
