<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/f/f7e5_f.css';
import '../../css/k/kmrbxx.css';
import '../../css/v/vfzm1b.css';
import '../../css/s/siu27j.css';
import '../../css/s/so-from-40.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c f7e5_f"/><path class="a0m25c kmrbxx"/><path class="a0m25c vfzm1b"/><path class="a0m25c siu27j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:coffee-arrow" /></template>
