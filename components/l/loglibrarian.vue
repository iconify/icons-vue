<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuup5mbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vuup5mbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:loglibrarian" /></template>
