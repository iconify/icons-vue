<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nap_aybed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nap_aybed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:database-fill-12" /></template>
