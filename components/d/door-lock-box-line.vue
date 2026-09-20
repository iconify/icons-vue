<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l92q-gx-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l92q-gx-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:door-lock-box-line" /></template>
