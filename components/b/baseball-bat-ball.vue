<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gafb6ybya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gafb6ybya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:baseball-bat-ball" /></template>
