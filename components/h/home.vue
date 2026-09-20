<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2hdh4u_p.css';
import '../../css/p/p7m4fxbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2hdh4u_p"/><path class="p7m4fxbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:home" /></template>
