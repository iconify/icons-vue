<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgapqibyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgapqibyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:blockquote-solid" /></template>
