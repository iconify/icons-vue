<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flkk7eaea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="flkk7eaea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:japanese-yen" /></template>
