<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3v46m1xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r3v46m1xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:displayport-fill" /></template>
