<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu410db3i.css';
import '../../css/u/u4lsadx-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mu410db3i"/><path class="u4lsadx-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:control-lun-solid" /></template>
