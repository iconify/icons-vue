<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkn258b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qkn258b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:double-diamond-tall" /></template>
