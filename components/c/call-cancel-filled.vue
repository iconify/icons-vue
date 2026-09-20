<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdldgbb_g.css';
import '../../css/d/d7q3yfbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdldgbb_g"/><path class="d7q3yfbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:call-cancel-filled" /></template>
