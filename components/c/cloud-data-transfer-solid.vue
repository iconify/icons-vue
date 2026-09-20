<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp56z7bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mp56z7bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cloud-data-transfer-solid" /></template>
