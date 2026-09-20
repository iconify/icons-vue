<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck3c2j_ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ck3c2j_ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:coffee-mug-solid" /></template>
