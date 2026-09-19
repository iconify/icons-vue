<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a36kvcc-u.css';
import '../../css/h/hm1y73b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a36kvcc-u"/><path class="hm1y73b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-cool" /></template>
