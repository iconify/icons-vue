<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt9qsmbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nt9qsmbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-stop-2" /></template>
