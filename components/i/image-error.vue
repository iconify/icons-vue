<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbgk870wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbgk870wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:image-error" /></template>
