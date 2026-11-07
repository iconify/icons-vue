<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byzboybhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="byzboybhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:add-folder-outline" /></template>
