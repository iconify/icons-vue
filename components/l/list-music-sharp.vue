<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii2j4fp2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii2j4fp2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-music-sharp" /></template>
