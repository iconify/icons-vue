<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4py-xsll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4py-xsll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-broken" /></template>
