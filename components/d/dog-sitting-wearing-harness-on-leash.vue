<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzw_ce6aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tzw_ce6aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-sitting-wearing-harness-on-leash" /></template>
