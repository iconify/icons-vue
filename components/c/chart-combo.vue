<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmaz-9vif.css';
import '../../css/x/xtkqegbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mmaz-9vif"/><path class="xtkqegbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-combo" /></template>
