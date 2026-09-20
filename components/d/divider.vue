<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj_tpbc1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj_tpbc1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:divider" /></template>
