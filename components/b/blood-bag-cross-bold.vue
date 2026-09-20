<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o300w3m6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o300w3m6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:blood-bag-cross-bold" /></template>
