<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9937jjxc.css';
import '../../css/b/b2uxm_bsm.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 m9937jjxc"/><path class="b2uxm_bsm clr-i-outline clr-i-outline-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:download-cloud-line" /></template>
