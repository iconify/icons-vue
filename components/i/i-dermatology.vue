<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7o3anbvb.css';
import '../../css/m/mgn5404zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="m7o3anbvb"/><path class="mgn5404zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-dermatology" /></template>
