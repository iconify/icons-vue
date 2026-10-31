<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8pqa-bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q8pqa-bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x3-20-solid" /></template>
