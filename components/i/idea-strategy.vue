<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-d7atbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-d7atbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:idea-strategy" /></template>
