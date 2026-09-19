<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdqndac6f.css';
import '../../css/u/ulfd5d-am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fdqndac6f"/><circle class="ulfd5d-am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-nuclear" /></template>
