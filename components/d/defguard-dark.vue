<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv2seupmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cv2seupmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:defguard-dark" /></template>
