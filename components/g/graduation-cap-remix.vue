<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp91arbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tp91arbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:graduation-cap-remix" /></template>
