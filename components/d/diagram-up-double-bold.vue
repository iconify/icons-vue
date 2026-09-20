<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vupesl-hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vupesl-hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:diagram-up-double-bold" /></template>
