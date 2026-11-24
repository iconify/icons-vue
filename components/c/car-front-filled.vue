<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh71qnbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rh71qnbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:car-front-filled" /></template>
