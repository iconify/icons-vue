<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxuj9db5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxuj9db5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dolphin" /></template>
