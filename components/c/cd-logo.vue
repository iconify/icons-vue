<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti_mu752a.css';
import '../../css/o/ocqrknbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ti_mu752a"/><path class="ocqrknbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:cd-logo" /></template>
