<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw-y_2o8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cw-y_2o8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:beyondcorp-enterprise-logo-block" /></template>
