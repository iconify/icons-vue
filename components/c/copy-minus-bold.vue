<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry6677b8a.css';
import '../../css/n/nazq8_bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ry6677b8a"/><path class="nazq8_bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copy-minus-bold" /></template>
