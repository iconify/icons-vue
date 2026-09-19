<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwiq4dznf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwiq4dznf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lamp-05" /></template>
