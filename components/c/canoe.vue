<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp1t9ibhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lp1t9ibhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:canoe" /></template>
