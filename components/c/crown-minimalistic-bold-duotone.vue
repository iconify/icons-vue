<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8nox1bbt.css';
import '../../css/o/ouxb72b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z8nox1bbt"/><path class="ouxb72b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-minimalistic-bold-duotone" /></template>
