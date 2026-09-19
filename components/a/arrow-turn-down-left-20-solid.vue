<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acjrvm-jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="acjrvm-jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-down-left-20-solid" /></template>
