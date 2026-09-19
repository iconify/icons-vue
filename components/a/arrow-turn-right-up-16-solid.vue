<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz778umpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rz778umpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-right-up-16-solid" /></template>
