<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pin2mcbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pin2mcbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:hotdog-outline" /></template>
