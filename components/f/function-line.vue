<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nopc6zb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nopc6zb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:function-line" /></template>
