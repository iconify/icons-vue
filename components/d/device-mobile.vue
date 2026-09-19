<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvx11z1dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bvx11z1dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:device-mobile" /></template>
