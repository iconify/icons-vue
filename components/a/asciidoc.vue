<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u11ifk20b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":439,"height":512};
const content = `<path class="u11ifk20b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:asciidoc" /></template>
