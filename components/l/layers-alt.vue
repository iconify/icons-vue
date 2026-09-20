<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaw7kx8vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaw7kx8vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:layers-alt" /></template>
