<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoeatstfv.css';
import '../../css/l/l06m6xpen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoeatstfv"/><path class="l06m6xpen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:airplay-filled" /></template>
