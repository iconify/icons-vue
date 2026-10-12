<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3wiavcio.css';
import '../../css/b/bno5nxbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3wiavcio"/><path clip-rule="evenodd" class="bno5nxbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-search-filled" /></template>
