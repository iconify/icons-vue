<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyyc1v_5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyyc1v_5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-triangle-down-filled" /></template>
