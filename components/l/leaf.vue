<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwbt9r8zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwbt9r8zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:leaf" /></template>
