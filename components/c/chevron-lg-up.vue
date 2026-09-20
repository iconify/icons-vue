<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_7bugblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l_7bugblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:chevron-lg-up" /></template>
