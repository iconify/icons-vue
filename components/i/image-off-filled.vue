<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmc7v17rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmc7v17rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:image-off-filled" /></template>
