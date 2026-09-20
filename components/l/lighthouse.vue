<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_n7etb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b_n7etb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lighthouse" /></template>
