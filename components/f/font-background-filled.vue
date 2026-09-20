<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwwfp2bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="nwwfp2bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:font-background-filled" /></template>
