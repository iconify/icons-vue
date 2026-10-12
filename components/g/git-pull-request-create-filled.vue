<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gml9_ib2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gml9_ib2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:git-pull-request-create-filled" /></template>
