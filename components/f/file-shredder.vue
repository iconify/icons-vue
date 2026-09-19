<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj2bybctk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj2bybctk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-shredder" /></template>
