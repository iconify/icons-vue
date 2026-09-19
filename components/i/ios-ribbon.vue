<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-s_g5rvf.css';
import '../../css/s/sfb9xk9fs.css';
import '../../css/o/ob232qb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-s_g5rvf"/><path class="sfb9xk9fs"/><path class="ob232qb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-ribbon" /></template>
