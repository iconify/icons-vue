<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wub9asb0k.css';
import '../../css/s/sgi1483fh.css';
import '../../css/v/vxtaxskvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wub9asb0k"/><path class="sgi1483fh"/><path class="vxtaxskvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:feed-in-20" /></template>
