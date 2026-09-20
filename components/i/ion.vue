<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm3f23fqe.css';
import '../../css/q/qwo6utarj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm3f23fqe"/><path class="qwo6utarj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ion" /></template>
