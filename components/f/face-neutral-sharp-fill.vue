<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2lw1wbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2lw1wbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-neutral-sharp-fill" /></template>
