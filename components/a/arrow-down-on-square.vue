<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-qe7cb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v-qe7cb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-down-on-square" /></template>
