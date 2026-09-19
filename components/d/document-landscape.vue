<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blbu05bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="blbu05bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:document-landscape" /></template>
