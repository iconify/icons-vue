<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8df1obis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8df1obis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:dropbox-logo-2" /></template>
