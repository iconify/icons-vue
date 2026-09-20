<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejb19ccpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ejb19ccpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-radius-solid" /></template>
