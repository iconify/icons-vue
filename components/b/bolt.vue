<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9lq89byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="q9lq89byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bolt" /></template>
