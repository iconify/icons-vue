<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3md_prhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u3md_prhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-minus-20-solid" /></template>
