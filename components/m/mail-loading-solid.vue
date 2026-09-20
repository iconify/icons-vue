<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q35acvs1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q35acvs1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:mail-loading-solid" /></template>
