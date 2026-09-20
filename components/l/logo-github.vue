<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhpx4tbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhpx4tbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-github" /></template>
