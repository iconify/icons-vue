<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/szxhkdbau.css';
import '../../css/n/n4g3xacqe.css';
import '../../css/r/r2kxiiuoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="szxhkdbau"/><path class="n4g3xacqe wm-a"/><path class="r2kxiiuoz wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-dot-solid" /></template>
