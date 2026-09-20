<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u136l-8rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u136l-8rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-favourite-bookmark-outline" /></template>
