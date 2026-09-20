<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm6wtzeab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm6wtzeab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-minus" /></template>
