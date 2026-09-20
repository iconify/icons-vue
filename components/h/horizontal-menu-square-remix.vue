<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgdh50j0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgdh50j0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:horizontal-menu-square-remix" /></template>
