<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j13wk_p2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j13wk_p2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:attach-square-filled" /></template>
