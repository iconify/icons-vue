<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aevmiibvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aevmiibvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-volume-mute" /></template>
