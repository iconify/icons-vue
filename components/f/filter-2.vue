<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovm_cjbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovm_cjbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:filter-2" /></template>
