<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsn8jgaeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="bsn8jgaeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:egg" /></template>
