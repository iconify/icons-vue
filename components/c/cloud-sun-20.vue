<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9w0q_b5k.css';
import '../../css/n/nc1vrqo3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p9w0q_b5k"/><path class="nc1vrqo3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sun-20" /></template>
