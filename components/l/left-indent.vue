<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laizaxi8c.css';
import '../../css/n/n32urigtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="laizaxi8c"/><path class="n32urigtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:left-indent" /></template>
