<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5u3jub2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u5u3jub2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:document-download" /></template>
