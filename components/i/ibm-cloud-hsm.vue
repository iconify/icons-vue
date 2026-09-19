<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs1m6rt0a.css';
import '../../css/o/onr7_4buh.css';
import '../../css/e/eqzj32bze.css';
import '../../css/o/obo5obcev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hs1m6rt0a"/><circle class="onr7_4buh"/><circle class="eqzj32bze"/><path class="obo5obcev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-hsm" /></template>
