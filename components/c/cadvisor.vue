<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwsm7kfyt.css';
import '../../css/x/xm99lzboj.css';
import '../../css/j/ja64cnb2a.css';
import '../../css/n/nf8s6zbdh.css';
import '../../css/i/i53b1ojoa.css';
import '../../css/x/xm6uyxb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwsm7kfyt"/><path class="xm99lzboj"/><path class="ja64cnb2a"/><path class="nf8s6zbdh"/><path class="i53b1ojoa"/><path class="xm6uyxb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cadvisor" /></template>
