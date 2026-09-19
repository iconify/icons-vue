<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_l8o78eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_l8o78eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:diameter" /></template>
