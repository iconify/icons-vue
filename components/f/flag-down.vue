<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2k7zsk0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2k7zsk0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-down" /></template>
