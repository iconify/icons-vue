<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0gzd41up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0gzd41up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fedex" /></template>
