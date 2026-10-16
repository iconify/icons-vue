<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqyen_7is.css';
import '../../css/c/cj85dubro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lqyen_7is"/><path class="cj85dubro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:extension-lead-20-bold" /></template>
