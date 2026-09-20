<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9di_yx8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k9di_yx8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:justice-hammer-solid" /></template>
