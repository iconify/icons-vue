<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-js8ibul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f-js8ibul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bandage-adhesive" /></template>
