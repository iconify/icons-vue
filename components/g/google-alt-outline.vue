<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr4nnobax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pr4nnobax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:google-alt-outline" /></template>
