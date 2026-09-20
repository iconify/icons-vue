<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2jxgcc7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2jxgcc7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hard-drive-sharp-fill" /></template>
