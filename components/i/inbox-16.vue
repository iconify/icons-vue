<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8t0y_b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g8t0y_b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:inbox-16" /></template>
