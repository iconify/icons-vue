<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww0sxhtpg.css';
import '../../css/s/skhazup6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww0sxhtpg"/><path class="skhazup6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cheese-filled" /></template>
