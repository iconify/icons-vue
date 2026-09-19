<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvivz2ben.css';
import '../../css/z/zznnyf-1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="cvivz2ben"/><path class="zznnyf-1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:file-1" /></template>
