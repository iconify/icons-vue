<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6xfamblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z6xfamblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:location-pin" /></template>
