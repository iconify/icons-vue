<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9v9jiznd.css';
import '../../css/z/z1pqwacjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f9v9jiznd"/><path class="z1pqwacjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-coffee-cup" /></template>
