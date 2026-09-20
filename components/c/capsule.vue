<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t635e0gnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t635e0gnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:capsule" /></template>
