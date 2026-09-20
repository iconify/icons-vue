<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwerzcbov.css';
import '../../css/n/n4xd9jpho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwerzcbov"/><path class="n4xd9jpho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hez" /></template>
