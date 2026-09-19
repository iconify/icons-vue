<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v88_xacul.css';
import '../../css/l/lwa5up2ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v88_xacul"/><path class="lwa5up2ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:info-octagon" /></template>
