<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd4od4bcx.css';
import '../../css/t/tm3vgc7aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd4od4bcx"/><path clip-rule="evenodd" class="tm3vgc7aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-arrow-down-light" /></template>
