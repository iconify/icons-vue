<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmj_u7gyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pmj_u7gyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:credit-card-5-solid" /></template>
