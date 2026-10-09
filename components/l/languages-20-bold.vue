<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4d3-1mti.css';
import '../../css/a/ay8umis1r.css';
import '../../css/o/o49-qrbbn.css';
import '../../css/i/iu_u5m5mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k4d3-1mti"/><path class="ay8umis1r"/><path class="o49-qrbbn"/><path class="iu_u5m5mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:languages-20-bold" /></template>
