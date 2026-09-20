<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqmqxhpqk.css';
import '../../css/n/n5t4ppego.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqmqxhpqk"/><path class="n5t4ppego"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bus-1" /></template>
