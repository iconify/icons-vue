<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj3j_obax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj3j_obax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bowl-chopsticks" /></template>
