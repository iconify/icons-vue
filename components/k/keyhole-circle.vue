<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj2_uqniq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj2_uqniq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:keyhole-circle" /></template>
