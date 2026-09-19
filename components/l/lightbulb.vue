<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s498vrbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s498vrbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:lightbulb" /></template>
