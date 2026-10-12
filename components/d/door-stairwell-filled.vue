<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuff21y9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uuff21y9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:door-stairwell-filled" /></template>
