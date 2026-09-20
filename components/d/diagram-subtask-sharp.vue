<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2itfyboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2itfyboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-subtask-sharp" /></template>
