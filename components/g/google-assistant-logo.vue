<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbfn4gbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbfn4gbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-assistant-logo" /></template>
