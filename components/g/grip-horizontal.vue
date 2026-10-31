<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/w/wnxw1k5ye.css';
import '../../css/u/urb6y16ft.css';
import '../../css/c/c4iuvactu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow wnxw1k5ye"/><path class="urb6y16ft wm-shadow"/><path class="c4iuvactu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:grip-horizontal" /></template>
