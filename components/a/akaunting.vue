<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knxmof92n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knxmof92n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:akaunting" /></template>
