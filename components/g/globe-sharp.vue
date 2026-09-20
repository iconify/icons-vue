<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzkw8_bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzkw8_bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-sharp" /></template>
