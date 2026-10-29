<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x01i_ccby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x01i_ccby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:globe-solid" /></template>
