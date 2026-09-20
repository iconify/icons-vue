<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqjzyv4lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqjzyv4lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ascn" /></template>
