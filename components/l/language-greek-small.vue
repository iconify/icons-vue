<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc2ln7gjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fc2ln7gjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-greek-small" /></template>
