<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhh_ol2fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhh_ol2fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:diners-club-line" /></template>
