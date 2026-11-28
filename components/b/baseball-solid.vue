<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztr0zpbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztr0zpbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:baseball-solid" /></template>
