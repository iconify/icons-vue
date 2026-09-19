<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a06oteb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a06oteb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-crown" /></template>
