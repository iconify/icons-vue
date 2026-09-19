<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njyl-vsgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njyl-vsgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-classic-hung-4-alt" /></template>
