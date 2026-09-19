<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtdfgyb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mtdfgyb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:left-arrow-circled-small" /></template>
