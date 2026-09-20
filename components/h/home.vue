<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/y/yc7hov.css';
import '../../css/l/lagu3m.css';
import '../../css/u/udfy8i.css';
import '../../css/z/zv7ueu.css';
import '../../css/s/so-from-18.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c yc7hov"/><path class="a0m25c lagu3m"/><path class="a0m25c udfy8i"/><path class="a0m25c zv7ueu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:home" /></template>
