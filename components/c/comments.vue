<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqnw9gbzk.css';
import '../../css/v/vzxnh3iad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqnw9gbzk"/><path class="vzxnh3iad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:comments" /></template>
