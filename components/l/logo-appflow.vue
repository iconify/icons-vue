<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuqgrccsg.css';
import '../../css/o/obu153b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yuqgrccsg"/><path class="obu153b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-appflow" /></template>
