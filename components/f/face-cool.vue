<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6xt707xs.css';
import '../../css/i/idlu6hbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j6xt707xs"/><path class="idlu6hbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-cool" /></template>
