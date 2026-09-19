<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nllflp_eh.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/d/dosjvkbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nllflp_eh"/><path class="bwibdw4bb"/><path class="dosjvkbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:disc" /></template>
