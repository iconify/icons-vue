<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa67-jbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fa67-jbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:3-plus" /></template>
