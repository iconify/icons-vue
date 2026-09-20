<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcv8ny-rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wcv8ny-rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:corner-down-left-solid" /></template>
