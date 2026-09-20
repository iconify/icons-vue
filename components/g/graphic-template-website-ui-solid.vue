<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qql3zx4xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qql3zx4xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:graphic-template-website-ui-solid" /></template>
