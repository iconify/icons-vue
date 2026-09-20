<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw4uddb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw4uddb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flask-line" /></template>
