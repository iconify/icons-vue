<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx--zl.css';
import '../../css/i/iw1iew.css';
import '../../css/k/kmrbxx.css';
import '../../css/y/y4wbml.css';
import '../../css/v/vfzm1b.css';
import '../../css/s/siu27j.css';
import '../../css/s/so-from-40.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx--zl iw1iew"/><path class="iw1iew kmrbxx y4wbml"/><path class="iw1iew vfzm1b y4wbml"/><path class="iw1iew siu27j y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:coffee-arrow-filled" /></template>
