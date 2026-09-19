<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhnr1xbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="hhnr1xbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:contao" /></template>
