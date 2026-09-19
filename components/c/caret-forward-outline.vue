<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_32zi80z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_32zi80z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:caret-forward-outline" /></template>
