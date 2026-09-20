<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-xvne0je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-xvne0je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-g-diamond-solid" /></template>
