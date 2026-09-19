<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlh4lswzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hlh4lswzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-female-0306m-outline" /></template>
