<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv1m-94fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv1m-94fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:border-clear" /></template>
