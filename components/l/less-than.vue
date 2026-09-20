<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0o14rb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y0o14rb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:less-than" /></template>
