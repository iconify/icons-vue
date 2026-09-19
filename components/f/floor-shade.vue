<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipejqhtoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipejqhtoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:floor-shade" /></template>
