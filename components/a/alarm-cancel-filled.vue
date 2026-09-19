<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dswxyebiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dswxyebiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alarm-cancel-filled" /></template>
