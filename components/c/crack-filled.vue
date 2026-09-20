<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttalljb2j.css';
import '../../css/p/p_n9afb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttalljb2j"/><path class="p_n9afb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:crack-filled" /></template>
