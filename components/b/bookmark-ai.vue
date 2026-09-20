<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlv0inh3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlv0inh3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-ai" /></template>
