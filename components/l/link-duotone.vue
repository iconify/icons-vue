<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9og_8wkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9og_8wkb primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:link-duotone" /></template>
