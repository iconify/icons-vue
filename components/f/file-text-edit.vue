<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrc1pubwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrc1pubwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-text-edit" /></template>
