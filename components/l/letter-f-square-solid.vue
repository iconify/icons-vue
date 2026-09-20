<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe3_xqmxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe3_xqmxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-f-square-solid" /></template>
