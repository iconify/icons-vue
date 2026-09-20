<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs34gqbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs34gqbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cookie-filled" /></template>
