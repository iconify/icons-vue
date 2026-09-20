<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz3ot1u3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pz3ot1u3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:bookmark-plus" /></template>
