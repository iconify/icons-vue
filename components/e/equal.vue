<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmkza5_pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmkza5_pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:equal" /></template>
