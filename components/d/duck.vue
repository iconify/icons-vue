<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubd38yi7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubd38yi7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:duck" /></template>
