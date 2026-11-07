<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seb4uo8hr.css';
import '../../css/b/b03wwil3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="seb4uo8hr"/><path class="b03wwil3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-check-minimalistic-bold-duotone" /></template>
