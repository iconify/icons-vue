<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifuc-ccmq.css';
import '../../css/q/qhzz97u4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ifuc-ccmq"/><path class="qhzz97u4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:envelope-open-solid" /></template>
