<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adh6zfbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adh6zfbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:google-outline" /></template>
