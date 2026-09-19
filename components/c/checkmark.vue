<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn_jpfb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":830};
const content = `<path class="qn_jpfb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:checkmark" /></template>
