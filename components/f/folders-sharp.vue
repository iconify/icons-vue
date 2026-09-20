<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkx4u2t6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkx4u2t6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folders-sharp" /></template>
