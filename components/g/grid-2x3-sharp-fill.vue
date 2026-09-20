<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibn--6bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibn--6bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x3-sharp-fill" /></template>
