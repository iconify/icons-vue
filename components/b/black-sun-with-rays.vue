<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c18lasbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c18lasbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-sun-with-rays" /></template>
