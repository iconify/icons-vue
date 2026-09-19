<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u72cutb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u72cutb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:lollipop" /></template>
