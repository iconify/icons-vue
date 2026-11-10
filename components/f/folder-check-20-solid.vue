<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcleg0b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tcleg0b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-check-20-solid" /></template>
