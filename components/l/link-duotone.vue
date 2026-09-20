<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpy_z2buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vpy_z2buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:link-duotone" /></template>
