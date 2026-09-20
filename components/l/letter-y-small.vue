<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxxlgqbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxxlgqbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-y-small" /></template>
