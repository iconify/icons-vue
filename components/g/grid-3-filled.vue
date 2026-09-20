<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oav3xe.css';
import '../../css/q/qtbnay.css';
import '../../css/o/o9qm1a.css';
import '../../css/j/jqrlmu.css';
import '../../css/s/so-from-12.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oav3xe qtbnay"/><path class="o9qm1a qtbnay"/><path class="jqrlmu qtbnay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:grid-3-filled" /></template>
