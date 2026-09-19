<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neudabg9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neudabg9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-shrink-02" /></template>
