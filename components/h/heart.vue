<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leszf0mru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="leszf0mru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:heart" /></template>
