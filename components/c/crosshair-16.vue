<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coc607b1m.css';
import '../../css/d/d0kk4rblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="coc607b1m"/><path clip-rule="evenodd" class="d0kk4rblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:crosshair-16" /></template>
