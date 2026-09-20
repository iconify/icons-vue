<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu5ljbbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu5ljbbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-down-sharp-fill" /></template>
