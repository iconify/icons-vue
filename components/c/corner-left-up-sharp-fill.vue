<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwlud-5vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwlud-5vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-left-up-sharp-fill" /></template>
