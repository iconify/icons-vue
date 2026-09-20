<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp5hlb-sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp5hlb-sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-collapse-sharp-two-tone" /></template>
