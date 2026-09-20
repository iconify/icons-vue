<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bulm8yy-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bulm8yy-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:clipboard-check" /></template>
