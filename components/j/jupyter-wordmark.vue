<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsgr4acwq.css';
import '../../css/q/qvr969ois.css';
import '../../css/w/wuqa13gqk.css';
import '../../css/j/j171pzbgu.css';
import '../../css/h/ha5b2dbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qsgr4acwq"/><path class="qvr969ois"/><path class="wuqa13gqk"/><path class="j171pzbgu"/><path class="ha5b2dbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:jupyter-wordmark" /></template>
