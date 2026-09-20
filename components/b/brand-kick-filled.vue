<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd4ak5pba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd4ak5pba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-kick-filled" /></template>
