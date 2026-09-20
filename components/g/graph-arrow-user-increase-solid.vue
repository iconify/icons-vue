<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kotf-_org.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kotf-_org"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:graph-arrow-user-increase-solid" /></template>
