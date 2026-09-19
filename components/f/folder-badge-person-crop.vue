<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-isl5zjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q-isl5zjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:folder-badge-person-crop" /></template>
