<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztworh.css';
import '../../css/f/fill-to-0.css';
import '../../css/d/d-gf8qwu.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztworh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-alt-twotone-loop" /></template>
