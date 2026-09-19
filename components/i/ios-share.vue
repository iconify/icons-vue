<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0fq7z9-w.css';
import '../../css/h/hzfhhfw2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d0fq7z9-w"/><path class="hzfhhfw2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-share" /></template>
