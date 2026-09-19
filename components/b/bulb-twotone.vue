<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9qe-eb2q.css';
import '../../css/k/kf_l1cpme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n9qe-eb2q"/><path class="kf_l1cpme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bulb-twotone" /></template>
