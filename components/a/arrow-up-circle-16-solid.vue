<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kejb9lbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kejb9lbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-circle-16-solid" /></template>
