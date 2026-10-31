<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkv3n0bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkv3n0bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:component-instance-duocolor-round" /></template>
