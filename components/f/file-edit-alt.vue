<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omfxs9b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omfxs9b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-edit-alt" /></template>
