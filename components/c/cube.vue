<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad0tddb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad0tddb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:cube" /></template>
