<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6dc5-vlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="x6dc5-vlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:id-badge" /></template>
