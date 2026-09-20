<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj6l9vbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj6l9vbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aurabal" /></template>
