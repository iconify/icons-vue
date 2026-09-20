<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im9_jacuo.css';
import '../../css/w/wjmq22vfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="im9_jacuo"/><path class="wjmq22vfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beekeeper-studio" /></template>
