<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgnivh30g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgnivh30g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-burj-al-arab" /></template>
