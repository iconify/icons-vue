<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yybeh6b4o.css';
import '../../css/r/rc1rp4d6j.css';
import '../../css/h/h2w2gxl4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yybeh6b4o"/><path class="rc1rp4d6j"/><path class="h2w2gxl4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gravity-base-48-bold" /></template>
