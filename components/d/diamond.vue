<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsd-6j50u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="lsd-6j50u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:diamond" /></template>
