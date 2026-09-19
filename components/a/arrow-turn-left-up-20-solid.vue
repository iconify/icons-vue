<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn4d29b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bn4d29b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-left-up-20-solid" /></template>
