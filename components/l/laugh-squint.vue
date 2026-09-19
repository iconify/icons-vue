<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_362bcck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="w_362bcck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:laugh-squint" /></template>
