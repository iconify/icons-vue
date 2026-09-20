<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v29gozgod.css';
import '../../css/m/mv0hob2-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v29gozgod"/><path class="mv0hob2-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:home" /></template>
