<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io_iyrrsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io_iyrrsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:battery-50" /></template>
