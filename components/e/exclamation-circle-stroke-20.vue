<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xphq9lb9l.css';
import '../../css/d/d32lng5vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xphq9lb9l"/><path class="d32lng5vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:exclamation-circle-stroke-20" /></template>
