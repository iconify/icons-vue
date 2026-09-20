<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf_itvb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf_itvb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:expand-down-filled" /></template>
