<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi5alzboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bi5alzboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:documenso-light" /></template>
