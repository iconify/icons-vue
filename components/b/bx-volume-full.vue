<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/himehxbog.css';
import '../../css/p/prj3bzzpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="himehxbog"/><path class="prj3bzzpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-volume-full" /></template>
