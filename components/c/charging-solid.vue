<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un_cf_ubk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="un_cf_ubk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:charging-solid" /></template>
