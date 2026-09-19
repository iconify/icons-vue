<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_3zaff5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_3zaff5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pint-outline" /></template>
