<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2u5z701y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2u5z701y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:arm-24px" /></template>
