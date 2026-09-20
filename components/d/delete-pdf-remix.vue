<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwsl0ug_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gwsl0ug_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:delete-pdf-remix" /></template>
