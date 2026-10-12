<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufmb-0o7z.css';
import '../../css/g/gddx20bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufmb-0o7z"/><path clip-rule="evenodd" class="gddx20bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:disc-3-filled" /></template>
