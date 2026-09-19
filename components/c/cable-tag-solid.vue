<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he_05f72i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="he_05f72i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cable-tag-solid" /></template>
