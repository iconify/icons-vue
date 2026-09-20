<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyhob48_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyhob48_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ease-out-control-point" /></template>
