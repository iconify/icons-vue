<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q702qcbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q702qcbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:delete-2" /></template>
