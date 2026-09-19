<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-vdfkb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x-vdfkb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-pressure-2" /></template>
