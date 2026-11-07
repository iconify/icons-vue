<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2-z8pdzu.css';
import '../../css/s/sn_zd46fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2-z8pdzu"/><path class="sn_zd46fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:export-bold" /></template>
