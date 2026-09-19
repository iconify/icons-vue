<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3-t6yl5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i3-t6yl5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-livestream" /></template>
