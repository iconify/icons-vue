<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo6jg5d0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo6jg5d0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:arlo-q" /></template>
