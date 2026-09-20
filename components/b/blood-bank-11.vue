<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj3orgbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="rj3orgbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:blood-bank-11" /></template>
