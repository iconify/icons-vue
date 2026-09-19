<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gac48jb7z.css';
import '../../css/b/butntgbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gac48jb7z"/><path class="butntgbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:iot-connect" /></template>
