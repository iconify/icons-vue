<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csme_7b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csme_7b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-down-sm" /></template>
