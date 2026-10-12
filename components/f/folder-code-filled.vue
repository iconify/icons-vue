<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obb4mh94a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obb4mh94a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-code-filled" /></template>
