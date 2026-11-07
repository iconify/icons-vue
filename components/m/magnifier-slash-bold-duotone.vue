<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl66i7bqg.css';
import '../../css/n/n8rwppsqt.css';
import '../../css/w/wrft_xvmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="n8rwppsqt"/><path class="wrft_xvmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-slash-bold-duotone" /></template>
