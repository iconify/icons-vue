<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxe00ibvs.css';
import '../../css/k/ka7rv-bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xxe00ibvs"/><path class="ka7rv-bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-imaging-alternative-mri-two" /></template>
