<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biy8w7b2k.css';
import '../../css/g/gq5qxpyae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biy8w7b2k"/><path class="gq5qxpyae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:folder-open-solid" /></template>
