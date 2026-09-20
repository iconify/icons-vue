<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqxrkqxhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qqxrkqxhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:frog-with-cartoon-eyes-and-open-mouth" /></template>
