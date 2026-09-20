<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsobnkbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsobnkbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-open-sharp-duotone" /></template>
