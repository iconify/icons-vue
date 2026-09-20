<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_n-gduge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_n-gduge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-alt-slash" /></template>
