<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2-5fvpnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2-5fvpnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-text" /></template>
