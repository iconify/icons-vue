<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib7m0zbcn.css';
import '../../css/e/ec2kgw3ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib7m0zbcn"/><path class="ec2kgw3ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:flip-up" /></template>
