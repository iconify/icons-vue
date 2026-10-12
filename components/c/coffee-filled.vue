<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjg-q19wd.css';
import '../../css/e/eqdi4qwvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vjg-q19wd"/><path class="eqdi4qwvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:coffee-filled" /></template>
