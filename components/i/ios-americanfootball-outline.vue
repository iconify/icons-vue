<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shqqhybdk.css';
import '../../css/r/rqafvib9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shqqhybdk"/><path class="rqafvib9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-americanfootball-outline" /></template>
