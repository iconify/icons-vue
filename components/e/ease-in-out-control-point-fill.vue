<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw_5fktgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw_5fktgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-in-out-control-point-fill" /></template>
