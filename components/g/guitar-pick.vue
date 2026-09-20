<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phc7xrc5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phc7xrc5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:guitar-pick" /></template>
