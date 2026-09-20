<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa_qoyf3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="oa_qoyf3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:flag-2" /></template>
