<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj6za9bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj6za9bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clipboard-solid" /></template>
