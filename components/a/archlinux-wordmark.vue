<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjeh93b6f.css';
import '../../css/h/hh3_j8aeb.css';
import '../../css/r/rqsccpugz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qjeh93b6f"/><path class="hh3_j8aeb"/><path class="rqsccpugz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:archlinux-wordmark" /></template>
