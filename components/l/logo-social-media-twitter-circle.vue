<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu6plhk2a.css';
import '../../css/m/mb34tibqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tu6plhk2a"/><path class="mb34tibqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-social-media-twitter-circle" /></template>
