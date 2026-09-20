<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk6g9lbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wk6g9lbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:affinity-designer-logo-block" /></template>
