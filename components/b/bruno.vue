<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgqejvb_u.css';
import '../../css/j/jcx6hxbdf.css';
import '../../css/x/xrbve6iev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cgqejvb_u"/><path class="jcx6hxbdf"/><path class="xrbve6iev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:bruno" /></template>
