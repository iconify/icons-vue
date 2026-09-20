<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iub38o1gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iub38o1gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:jersey-pound" /></template>
