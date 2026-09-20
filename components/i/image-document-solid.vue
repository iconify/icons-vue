<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c57dn841e.css';
import '../../css/z/z31349b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="c57dn841e"/><path class="z31349b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:image-document-solid" /></template>
