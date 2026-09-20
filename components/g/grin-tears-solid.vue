<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryr9acblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ryr9acblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grin-tears-solid" /></template>
