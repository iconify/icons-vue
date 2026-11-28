<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajqbxzbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajqbxzbxv primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-to-line-duotone" /></template>
