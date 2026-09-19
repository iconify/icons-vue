<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3vra2bpp.css';
import '../../css/k/k80k31tai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3vra2bpp"/><path class="k80k31tai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-landscape" /></template>
