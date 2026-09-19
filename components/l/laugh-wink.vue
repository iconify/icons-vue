<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1cbjxi4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="k1cbjxi4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:laugh-wink" /></template>
