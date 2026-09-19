<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw0njuuzd.css';
import '../../css/r/rssdfuhft.css';
import '../../css/y/ywin52edh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qw0njuuzd"/><path class="rssdfuhft"/><path class="ywin52edh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:doctrine-wordmark" /></template>
