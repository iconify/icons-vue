<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odoue8rqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odoue8rqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hr1" /></template>
