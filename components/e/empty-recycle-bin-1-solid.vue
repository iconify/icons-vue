<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu3trccue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mu3trccue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:empty-recycle-bin-1-solid" /></template>
