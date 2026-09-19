<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcu0wuc1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lcu0wuc1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:eyeglasses" /></template>
