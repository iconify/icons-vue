<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk3yze2hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1025};
const content = `<path class="jk3yze2hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cctv" /></template>
