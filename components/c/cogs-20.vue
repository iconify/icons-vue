<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc234ccnu.css';
import '../../css/v/v0_7k5btb.css';
import '../../css/r/rbyjwpwup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kc234ccnu"/><path class="v0_7k5btb"/><path class="rbyjwpwup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cogs-20" /></template>
