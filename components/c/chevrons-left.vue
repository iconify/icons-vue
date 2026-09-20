<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2vzr5v5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-5};
const content = `<path class="m2vzr5v5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-left" /></template>
