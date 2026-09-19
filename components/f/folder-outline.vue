<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui6f1wb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ui6f1wb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:folder-outline" /></template>
