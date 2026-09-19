<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlx9fpbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlx9fpbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:feather-plus" /></template>
