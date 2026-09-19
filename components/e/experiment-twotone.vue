<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odtla-seg.css';
import '../../css/n/ns3hbpbni.css';
import '../../css/p/ppyfuefwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="odtla-seg"/><path class="ns3hbpbni"/><path class="ppyfuefwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:experiment-twotone" /></template>
