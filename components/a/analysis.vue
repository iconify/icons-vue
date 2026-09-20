<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae5_81b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ae5_81b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:analysis" /></template>
