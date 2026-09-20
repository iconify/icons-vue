<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4gh0-bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4gh0-bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:browser-build-remix" /></template>
