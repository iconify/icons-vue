<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebm2gkc5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ebm2gkc5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kma" /></template>
