<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgya-abtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hgya-abtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heart-black-suit-small" /></template>
