<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiblb-bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="wiblb-bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:fast-forward-circle-f" /></template>
