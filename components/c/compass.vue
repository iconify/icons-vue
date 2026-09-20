<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzrfr_byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzrfr_byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:compass" /></template>
