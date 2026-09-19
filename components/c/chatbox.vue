<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya5otobje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ya5otobje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chatbox" /></template>
