<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf7059b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rf7059b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:alipay-small" /></template>
