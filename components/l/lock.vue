<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvd_t7aci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvd_t7aci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:lock" /></template>
