<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo68ar.css';
import '../../css/q/qa-o7h.css';
import '../../css/e/ewvm5y.css';
import '../../css/k/kullsj.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo68ar qa-o7h"/><path class="ewvm5y qa-o7h"/><path class="kullsj qa-o7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:grid-3" /></template>
