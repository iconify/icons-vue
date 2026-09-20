<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn4vgeb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn4vgeb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-filled" /></template>
