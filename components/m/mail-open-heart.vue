<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3wroybub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3wroybub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mail-open-heart" /></template>
