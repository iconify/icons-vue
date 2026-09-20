<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmtg06bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wmtg06bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folder-x-solid" /></template>
