<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqjart1so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fqjart1so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:hammer" /></template>
