<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hszia39-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="hszia39-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:id-badge" /></template>
