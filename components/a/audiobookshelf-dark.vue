<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz238-fks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xz238-fks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audiobookshelf-dark" /></template>
