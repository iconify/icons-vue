<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clh-9mboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="clh-9mboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cloud-off-solid" /></template>
