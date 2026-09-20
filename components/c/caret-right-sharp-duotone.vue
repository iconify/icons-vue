<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1vs7vpjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1vs7vpjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-right-sharp-duotone" /></template>
