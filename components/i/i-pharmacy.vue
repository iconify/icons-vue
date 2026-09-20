<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdatwkffh.css';
import '../../css/u/ux686dk8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bdatwkffh"/><path class="ux686dk8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-pharmacy" /></template>
