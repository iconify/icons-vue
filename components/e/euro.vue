<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bij7l3q8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bij7l3q8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:euro" /></template>
