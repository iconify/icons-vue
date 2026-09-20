<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi0s3acun.css';
import '../../css/w/w_ul5gqcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi0s3acun"/><path class="w_ul5gqcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:castle-filled" /></template>
