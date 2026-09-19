<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft7a-7c1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ft7a-7c1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:floppy-disk" /></template>
