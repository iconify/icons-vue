<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_f65xs6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z_f65xs6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:artist-palette" /></template>
