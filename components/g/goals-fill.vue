<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp-b7wzwg.css';
import '../../css/w/wsg3jcbeq.css';
import '../../css/f/f430c2b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp-b7wzwg"/><path class="wsg3jcbeq"/><path class="f430c2b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:goals-fill" /></template>
