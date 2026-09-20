<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deegn0b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="deegn0b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:expand-less-square-fill" /></template>
