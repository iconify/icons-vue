<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfl-fcnvq.css';
import '../../css/v/vbvjxkbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfl-fcnvq"/><path class="vbvjxkbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:biohazard-filled" /></template>
