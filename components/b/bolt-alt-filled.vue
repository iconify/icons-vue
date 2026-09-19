<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv-3-ac2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv-3-ac2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bolt-alt-filled" /></template>
