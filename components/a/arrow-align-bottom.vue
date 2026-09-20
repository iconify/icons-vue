<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/l/l3xoro.css';
import '../../css/n/nazh2e.css';
import '../../css/q/qv8hvr.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c l3xoro"/><path class="a0m25c nazh2e"/><path class="a0m25c qv8hvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-align-bottom" /></template>
