<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pknpwpb5q.css';
import '../../css/l/l2nst-b0v.css';
import '../../css/k/ks5mnsbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pknpwpb5q"/><path class="l2nst-b0v"/><path class="ks5mnsbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:clinic-medical" /></template>
