<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r06i5gaqp.css';
import '../../css/z/zk-ob16tw.css';
import '../../css/l/lhz7cds8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r06i5gaqp"/><path class="zk-ob16tw"/><path class="lhz7cds8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hinge-20" /></template>
