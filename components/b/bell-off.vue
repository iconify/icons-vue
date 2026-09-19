<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dywcsz9la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dywcsz9la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bell-off" /></template>
