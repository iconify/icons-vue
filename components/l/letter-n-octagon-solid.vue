<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvoio1bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvoio1bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-n-octagon-solid" /></template>
