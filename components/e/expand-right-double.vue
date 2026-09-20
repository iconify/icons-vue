<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf9yt7bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf9yt7bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-right-double" /></template>
