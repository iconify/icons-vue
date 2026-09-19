<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_tzv3i3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_tzv3i3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:alert-circled" /></template>
