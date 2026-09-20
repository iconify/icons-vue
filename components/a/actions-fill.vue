<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vflu5yb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vflu5yb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:actions-fill" /></template>
