<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p67v0bc-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p67v0bc-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:jsx-alt" /></template>
