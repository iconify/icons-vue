<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhppmkbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhppmkbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lvl" /></template>
