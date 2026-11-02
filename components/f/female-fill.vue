<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxmkffbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxmkffbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:female-fill" /></template>
