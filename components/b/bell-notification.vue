<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr29mbbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr29mbbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bell-notification" /></template>
