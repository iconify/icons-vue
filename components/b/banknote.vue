<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5a7rwu8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5a7rwu8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote" /></template>
