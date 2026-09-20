<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5c9g5bsj.css';
import '../../css/z/zoxwfdcwf.css';
import '../../css/s/su0illb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5c9g5bsj"/><path class="zoxwfdcwf"/><path class="su0illb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:cloud-download" /></template>
