<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps7v1ibub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ps7v1ibub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:flask-fill" /></template>
