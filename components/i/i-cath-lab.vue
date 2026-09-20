<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwigj8bqa.css';
import '../../css/f/fvz0x3bpb.css';
import '../../css/z/zg0gl4b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dwigj8bqa"/><path class="fvz0x3bpb"/><path class="zg0gl4b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-cath-lab" /></template>
