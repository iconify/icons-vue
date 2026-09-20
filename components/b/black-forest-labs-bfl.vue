<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cambhtbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cambhtbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:black-forest-labs-bfl" /></template>
