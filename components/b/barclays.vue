<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh1n3196e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh1n3196e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:barclays" /></template>
