<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqm1_6bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="tqm1_6bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:film-filled" /></template>
