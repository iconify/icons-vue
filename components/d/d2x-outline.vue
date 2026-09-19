<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xerfjbcrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xerfjbcrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:d2x-outline" /></template>
