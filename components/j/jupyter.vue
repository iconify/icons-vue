<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvr969ois.css';
import '../../css/w/wuqa13gqk.css';
import '../../css/w/wsyyf2bqs.css';
import '../../css/q/qw_fs9bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qvr969ois"/><path class="wuqa13gqk"/><path class="wsyyf2bqs"/><path class="qw_fs9bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:jupyter" /></template>
