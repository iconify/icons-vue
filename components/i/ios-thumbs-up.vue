<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhso_9btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lhso_9btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-thumbs-up" /></template>
