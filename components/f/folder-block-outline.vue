<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w71c_izcc.css';
import '../../css/v/vawhvpbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w71c_izcc"/><path clip-rule="evenodd" class="vawhvpbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-block-outline" /></template>
