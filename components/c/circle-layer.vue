<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8xe1abcy.css';
import '../../css/m/mjic8l8dj.css';
import '../../css/a/ard9wdwyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8xe1abcy"/><circle class="mjic8l8dj"/><path class="ard9wdwyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:circle-layer" /></template>
