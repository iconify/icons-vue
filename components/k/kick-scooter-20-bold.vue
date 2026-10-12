<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9astq9iv.css';
import '../../css/t/ts6ghieqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c9astq9iv"/><path class="ts6ghieqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kick-scooter-20-bold" /></template>
