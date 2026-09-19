<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trbai4bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trbai4bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:factory" /></template>
