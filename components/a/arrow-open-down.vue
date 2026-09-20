<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/y/yt7y4i.css';
import '../../css/v/vmy1_d.css';
import '../../css/v/vmphcs.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c yt7y4i"/><path class="a0m25c vmy1_d"/><path class="a0m25c vmphcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-open-down" /></template>
