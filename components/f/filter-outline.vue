<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz-n4tbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mz-n4tbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:filter-outline" /></template>
