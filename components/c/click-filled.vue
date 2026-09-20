<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y279e5bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y279e5bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:click-filled" /></template>
