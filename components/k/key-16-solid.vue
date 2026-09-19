<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1ec8bbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k1ec8bbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:key-16-solid" /></template>
