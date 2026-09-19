<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqf30sr5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iqf30sr5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:chrome-outline" /></template>
