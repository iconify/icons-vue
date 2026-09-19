<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmt-9eb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dmt-9eb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bell-circle" /></template>
