<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgx22db5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="bgx22db5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:folderalt" /></template>
