<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs8p12bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="bs8p12bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:alien" /></template>
