<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt6oa8btc.css';
import '../../css/n/n2b3ufqkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vt6oa8btc"/><path class="n2b3ufqkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pause" /></template>
