<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvgr08bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvgr08bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:footprints-filled" /></template>
