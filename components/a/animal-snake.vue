<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4_kz36oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r4_kz36oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-snake" /></template>
