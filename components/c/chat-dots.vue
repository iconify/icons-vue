<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8-js_buo.css';
import '../../css/t/t94zb2zbz.css';
import '../../css/d/d235ln02k.css';
import '../../css/k/k5c3-bbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q8-js_buo"/><ellipse class="t94zb2zbz"/><ellipse class="d235ln02k"/><ellipse class="k5c3-bbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:chat-dots" /></template>
