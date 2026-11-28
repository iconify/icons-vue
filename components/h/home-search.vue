<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnrdznbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnrdznbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:home-search" /></template>
