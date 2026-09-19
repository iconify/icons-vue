<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwg97objp.css';
import '../../css/h/hxjbwwbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwg97objp"/><path class="hxjbwwbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-amazon" /></template>
