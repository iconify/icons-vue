<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-d90l.css';
import '../../css/i/iw1iew.css';
import '../../css/r/r3cp3p.css';
import '../../css/s/so-to-14.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-d90l iw1iew"/><path class="iw1iew r3cp3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:confirm-circle-twotone-to-circle-twotone-transition" /></template>
