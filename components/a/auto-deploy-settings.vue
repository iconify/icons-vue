<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_73dsbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o_73dsbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:auto-deploy-settings" /></template>
