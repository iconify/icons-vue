<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkozawy4w.css';
import '../../css/b/b0mwi-brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkozawy4w"/><path clip-rule="evenodd" class="b0mwi-brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-check-outline" /></template>
