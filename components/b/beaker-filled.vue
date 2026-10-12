<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w717xbb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w717xbb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:beaker-filled" /></template>
