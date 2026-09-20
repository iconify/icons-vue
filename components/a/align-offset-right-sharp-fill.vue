<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrmll9g5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrmll9g5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-offset-right-sharp-fill" /></template>
