<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rty09svnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rty09svnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:heart" /></template>
