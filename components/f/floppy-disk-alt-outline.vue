<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm78tdbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm78tdbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:floppy-disk-alt-outline" /></template>
