<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtsx69eye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wtsx69eye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-up-from-bracket" /></template>
