<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k58n_0uxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k58n_0uxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-small-right-20-solid" /></template>
