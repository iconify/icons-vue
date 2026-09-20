<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl4iseoju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl4iseoju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:check-double" /></template>
