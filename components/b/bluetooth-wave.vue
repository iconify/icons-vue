<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qycm1k8wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qycm1k8wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bluetooth-wave" /></template>
