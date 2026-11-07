<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhgdmdlsz.css';
import '../../css/u/u-6gmvb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fhgdmdlsz"/><path class="u-6gmvb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bar-chair-bold-duotone" /></template>
