<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpw4bybvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rpw4bybvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folder-tick-solid" /></template>
