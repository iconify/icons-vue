<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gctk9mbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gctk9mbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:alpha" /></template>
