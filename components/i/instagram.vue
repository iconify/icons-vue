<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ary96kbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":680,"height":694};
const content = `<path class="ary96kbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:instagram" /></template>
