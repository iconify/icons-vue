<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u96dugbci.css';
import '../../css/j/j-o7--b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="u96dugbci"/><path class="j-o7--b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:battery-dead" /></template>
