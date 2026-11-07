<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmnoaub3f.css';
import '../../css/y/y4c08ncxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bmnoaub3f"/><path class="y4c08ncxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-heart-minimalistic-bold-duotone" /></template>
