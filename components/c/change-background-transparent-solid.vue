<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6rrcnb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x6rrcnb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:change-background-transparent-solid" /></template>
