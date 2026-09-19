<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj1tylb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj1tylb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:bank-solid" /></template>
