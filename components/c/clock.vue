<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckfku8bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ckfku8bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:clock" /></template>
