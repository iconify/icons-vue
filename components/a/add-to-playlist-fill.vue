<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnoox0nod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnoox0nod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:add-to-playlist-fill" /></template>
