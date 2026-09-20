<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4kxk4k1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="y4kxk4k1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-mapping-filled" /></template>
