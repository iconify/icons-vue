<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk7b9xbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk7b9xbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-heart" /></template>
