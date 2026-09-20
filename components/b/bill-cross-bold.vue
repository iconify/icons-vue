<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnx3lyb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xnx3lyb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:bill-cross-bold" /></template>
