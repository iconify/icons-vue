<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbiwg9rpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pbiwg9rpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:hammer" /></template>
