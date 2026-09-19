<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez4qt3bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez4qt3bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-1-light" /></template>
