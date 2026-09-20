<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qccno4t1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qccno4t1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bracket-round" /></template>
