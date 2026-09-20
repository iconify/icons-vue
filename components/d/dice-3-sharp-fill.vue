<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md39-n46g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md39-n46g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-3-sharp-fill" /></template>
