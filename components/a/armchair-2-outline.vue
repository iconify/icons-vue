<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eobcxt-xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eobcxt-xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:armchair-2-outline" /></template>
