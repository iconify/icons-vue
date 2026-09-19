<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dob_ddbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dob_ddbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:anyway-fm" /></template>
