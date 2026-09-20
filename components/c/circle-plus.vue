<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz3k9hb8j.css';
import '../../css/y/yl2xz9yma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wz3k9hb8j"/><path class="yl2xz9yma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:circle-plus" /></template>
