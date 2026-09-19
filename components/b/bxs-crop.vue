<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1b4hxe1k.css';
import '../../css/i/inq217r_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1b4hxe1k"/><path class="inq217r_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-crop" /></template>
