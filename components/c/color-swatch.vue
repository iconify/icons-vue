<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wwci4obui.css';
import '../../css/a/ar7v4zcbf.css';
import '../../css/m/mv28m9o7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wwci4obui"/><path class="ar7v4zcbf"/><path class="mv28m9o7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:color-swatch" /></template>
