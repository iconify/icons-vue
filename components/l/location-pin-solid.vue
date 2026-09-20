<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq5cfnbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fq5cfnbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:location-pin-solid" /></template>
