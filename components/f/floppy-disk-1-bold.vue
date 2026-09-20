<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_ha40bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ha40bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:floppy-disk-1-bold" /></template>
