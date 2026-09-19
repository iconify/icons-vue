<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybwzvccuq.css';
import '../../css/o/ozud7nbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ybwzvccuq"/><path class="ozud7nbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chevron-forward-circle-outline" /></template>
