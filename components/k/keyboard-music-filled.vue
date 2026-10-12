<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fer3w3w-u.css';
import '../../css/p/pairkob_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fer3w3w-u"/><path clip-rule="evenodd" class="pairkob_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:keyboard-music-filled" /></template>
