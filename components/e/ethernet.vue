<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il78lqboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il78lqboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:ethernet" /></template>
