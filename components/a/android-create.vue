<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5z1hnb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5z1hnb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-create" /></template>
