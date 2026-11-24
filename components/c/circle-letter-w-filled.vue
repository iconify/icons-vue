<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxzwktx0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxzwktx0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-w-filled" /></template>
