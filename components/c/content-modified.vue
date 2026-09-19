<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaczkol8s.css';
import '../../css/k/k2yt7cn9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaczkol8s"/><path class="k2yt7cn9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:content-modified" /></template>
