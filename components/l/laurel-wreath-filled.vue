<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2d4ctjbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2d4ctjbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:laurel-wreath-filled" /></template>
