<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v08s5_dtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v08s5_dtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hackster" /></template>
