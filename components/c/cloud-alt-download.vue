<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc2fcx.css';
import '../../css/j/jyt2ef.css';
import '../../css/s/so-from-60.css';
import '../../css/d/d-es1ygv.css';
import '../../css/d/d-wrh7yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc2fcx"/><path class="jyt2ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-alt-download" /></template>
