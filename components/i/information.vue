<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un_rqmbfz.css';
import '../../css/j/ju2zpyrzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="un_rqmbfz"/><circle class="ju2zpyrzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:information" /></template>
