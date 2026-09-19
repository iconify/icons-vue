<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibmndspam.css';
import '../../css/n/nb7pxabat.css';
import '../../css/d/dwcqehbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ibmndspam"/><circle class="nb7pxabat"/><circle class="dwcqehbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:color-filter-outline" /></template>
