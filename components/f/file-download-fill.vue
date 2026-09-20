<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3va__60v.css';
import '../../css/r/r8hicpb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3va__60v"/><path class="r8hicpb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:file-download-fill" /></template>
