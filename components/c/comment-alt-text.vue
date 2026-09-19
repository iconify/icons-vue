<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk6vsqjki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="pk6vsqjki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment-alt-text" /></template>
