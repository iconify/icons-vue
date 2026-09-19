<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zessfchne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="zessfchne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dropbox" /></template>
