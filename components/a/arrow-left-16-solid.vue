<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0jek1b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r0jek1b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-left-16-solid" /></template>
