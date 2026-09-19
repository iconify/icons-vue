<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhmqpzncy.css';
import '../../css/x/xu8t15bjf.css';
import '../../css/z/zboiubcgk.css';
import '../../css/x/xnhmzobai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bhmqpzncy"/><path class="xu8t15bjf"/><path class="zboiubcgk"/><path class="xnhmzobai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:android-wordmark" /></template>
