<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zicf9cb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="zicf9cb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:filemanager" /></template>
