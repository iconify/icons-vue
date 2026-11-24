<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uopjj7bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uopjj7bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lectern-filled" /></template>
