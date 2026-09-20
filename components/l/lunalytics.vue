<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcz9gmb8w.css';
import '../../css/v/vi3jb3b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wcz9gmb8w"/><path class="vi3jb3b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lunalytics" /></template>
