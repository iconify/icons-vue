<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlcke6kyc.css';
import '../../css/r/r4v-mt3za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlcke6kyc"/><path class="r4v-mt3za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-camera" /></template>
