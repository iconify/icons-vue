<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9adr-b_h.css';
import '../../css/d/d7q3yfbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9adr-b_h"/><path class="d7q3yfbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:call-incoming-filled" /></template>
