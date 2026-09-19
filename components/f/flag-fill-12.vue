<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2w0dfbzz.css';
import '../../css/x/xjlu6cc0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v2w0dfbzz"/><path class="xjlu6cc0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:flag-fill-12" /></template>
