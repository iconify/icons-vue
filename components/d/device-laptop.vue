<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdvycsbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdvycsbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-laptop" /></template>
