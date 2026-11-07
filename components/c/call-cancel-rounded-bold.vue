<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-r_0lb5z.css';
import '../../css/c/cfzav0mxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-r_0lb5z"/><path class="cfzav0mxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-cancel-rounded-bold" /></template>
