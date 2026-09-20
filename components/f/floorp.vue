<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnpwc3blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnpwc3blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:floorp" /></template>
