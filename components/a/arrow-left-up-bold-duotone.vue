<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf863cbsv.css';
import '../../css/z/zfmuiycex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf863cbsv"/><path class="zfmuiycex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-up-bold-duotone" /></template>
