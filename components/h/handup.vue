<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shppmgbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":704,"height":1024};
const content = `<path class="shppmgbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:handup" /></template>
