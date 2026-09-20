<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq-e8xbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cq-e8xbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:group-meeting-approval-solid" /></template>
