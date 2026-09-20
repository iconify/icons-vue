<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkx37hb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkx37hb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-type-corner-sharp" /></template>
