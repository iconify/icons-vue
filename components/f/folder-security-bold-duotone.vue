<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl-98b13w.css';
import '../../css/c/cq-7z0vfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl-98b13w"/><path clip-rule="evenodd" class="cq-7z0vfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-security-bold-duotone" /></template>
