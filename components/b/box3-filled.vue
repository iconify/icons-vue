<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmvg3yb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmvg3yb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:box3-filled" /></template>
