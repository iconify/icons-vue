<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7asodbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7asodbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:govee-h6076" /></template>
