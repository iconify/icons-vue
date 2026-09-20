<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gja2j7b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gja2j7b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-with-shekel" /></template>
