<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue1e12bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ue1e12bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-info-fill" /></template>
