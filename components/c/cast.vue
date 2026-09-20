<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amsjd9bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="amsjd9bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cast" /></template>
