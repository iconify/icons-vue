<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk_tm6ard.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tk_tm6ard"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:input-latin-lower-letters" /></template>
