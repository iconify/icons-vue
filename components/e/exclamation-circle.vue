<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny0jd2rar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ny0jd2rar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:exclamation-circle" /></template>
