<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-585ybje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r-585ybje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-swiss-franc-filled" /></template>
