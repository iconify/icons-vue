<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxyn5kb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxyn5kb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lemmy" /></template>
