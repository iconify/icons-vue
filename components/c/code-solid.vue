<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am65ptyzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="am65ptyzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:code-solid" /></template>
