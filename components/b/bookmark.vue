<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl8cp6tgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl8cp6tgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bookmark" /></template>
