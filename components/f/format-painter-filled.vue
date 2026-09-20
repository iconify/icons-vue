<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of6l21bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of6l21bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:format-painter-filled" /></template>
