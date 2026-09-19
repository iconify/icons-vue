<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tynrwvp-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tynrwvp-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bold-16-solid" /></template>
