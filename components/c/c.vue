<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0gz3gb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z0gz3gb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:c" /></template>
