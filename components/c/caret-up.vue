<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuvwx4b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuvwx4b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:caret-up" /></template>
