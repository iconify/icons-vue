<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qttew1k1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qttew1k1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:livejournal" /></template>
