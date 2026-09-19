<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4y4hbm4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f4y4hbm4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-up-right-16-solid" /></template>
