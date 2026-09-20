<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0d1xbb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0d1xbb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:loudspeaker-filled" /></template>
