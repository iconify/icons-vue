<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndh4a3bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ndh4a3bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:feathub-logo-block" /></template>
