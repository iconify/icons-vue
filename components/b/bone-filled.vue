<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aupw2dbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aupw2dbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bone-filled" /></template>
