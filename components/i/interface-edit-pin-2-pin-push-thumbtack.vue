<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5hztnb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w5hztnb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-pin-2-pin-push-thumbtack" /></template>
