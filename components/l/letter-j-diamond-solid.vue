<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji-_atb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji-_atb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-j-diamond-solid" /></template>
