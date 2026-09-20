<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjjp56bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sjjp56bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:creative-commons-logo-solid" /></template>
