<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shr813boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shr813boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audiobookshelf-light" /></template>
