<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/m/m9j5ub.css';
import '../../css/f/fyy_6k.css';
import '../../css/s/so-from-14.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c m9j5ub"/><path class="a0m25c fyy_6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrows-vertical-alt" /></template>
