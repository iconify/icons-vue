<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7o_6ab8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7o_6ab8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-crm-dark" /></template>
