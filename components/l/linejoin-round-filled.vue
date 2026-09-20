<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb-9x3bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kb-9x3bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:linejoin-round-filled" /></template>
