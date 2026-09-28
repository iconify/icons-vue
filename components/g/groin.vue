<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gehq5_fws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gehq5_fws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:groin" /></template>
