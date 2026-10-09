<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b10s5pbto.css';
import '../../css/h/hymlskbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b10s5pbto"/><path class="hymlskbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fridge-48-bold" /></template>
