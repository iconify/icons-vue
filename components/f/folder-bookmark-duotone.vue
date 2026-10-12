<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vpxm9bbsu.css';
import '../../css/a/ac_vfwbhy.css';
import '../../css/y/y7rf6wbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vpxm9bbsu"/><path class="ac_vfwbhy"/><path class="y7rf6wbpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-bookmark-duotone" /></template>
