<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtzp2h9ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtzp2h9ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:horizontal-top-left-main" /></template>
