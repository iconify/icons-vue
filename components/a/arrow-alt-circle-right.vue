<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehrol8p9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ehrol8p9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-alt-circle-right" /></template>
