<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il7_fobub.css';
import '../../css/q/qty0zwbsq.css';
import '../../css/f/fagpc2blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il7_fobub"/><path class="qty0zwbsq"/><path class="fagpc2blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:layers-fill" /></template>
