<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjp8o5b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjp8o5b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fritzbox-7530" /></template>
