<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7a2x58go.css';
import '../../css/j/jmmn-h0hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7a2x58go"/><path class="jmmn-h0hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:clock-three" /></template>
