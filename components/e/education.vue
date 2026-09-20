<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0zucx8cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x0zucx8cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:education" /></template>
