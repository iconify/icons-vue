<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2bo8ohrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2bo8ohrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ease-out-control-point" /></template>
