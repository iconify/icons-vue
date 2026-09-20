<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh404cczq.css';
import '../../css/p/p343mol7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh404cczq"/><path clip-rule="evenodd" class="p343mol7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-multiple-duotone" /></template>
