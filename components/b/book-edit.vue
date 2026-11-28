<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfs850qku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfs850qku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-edit" /></template>
