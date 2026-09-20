<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x65263l8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x65263l8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:feathub-logo" /></template>
