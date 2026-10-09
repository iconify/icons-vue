<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xypximg7a.css';
import '../../css/b/bqvhui-iq.css';
import '../../css/k/k167alb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xypximg7a"/><path class="bqvhui-iq"/><path class="k167alb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:home-48" /></template>
