<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu15qfa1m.css';
import '../../css/j/j0smd1g0j.css';
import '../../css/w/wsm6lx-8z.css';
import '../../css/p/piv5izbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wu15qfa1m"/><path class="j0smd1g0j"/><path class="wsm6lx-8z"/><path class="piv5izbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:elix" /></template>
