<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb1o4ibht.css';
import '../../css/n/ngyu4emsk.css';
import '../../css/x/xin1hzb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="pb1o4ibht"/><path class="ngyu4emsk"/><path class="xin1hzb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:dk-4x3" /></template>
