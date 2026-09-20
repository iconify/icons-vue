<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7agr4acm.css';
import '../../css/r/r8hicpb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7agr4acm"/><path class="r8hicpb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:file-upload-fill" /></template>
