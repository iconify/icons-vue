<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u--wa7b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u--wa7b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kick-scooter-bold" /></template>
