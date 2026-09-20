<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po02n3bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="po02n3bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:html5-solid" /></template>
