<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ievdxcc9u.css';
import '../../css/x/xcuj9xz1r.css';
import '../../css/c/cfvelzb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ievdxcc9u"/><path class="xcuj9xz1r"/><path class="cfvelzb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:layers" /></template>
