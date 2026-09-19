<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de1slkgpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="de1slkgpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:external-link-square" /></template>
