<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyx6xc57b.css';
import '../../css/y/yxi16mj3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iyx6xc57b"/><path class="yxi16mj3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:1panel-dark" /></template>
