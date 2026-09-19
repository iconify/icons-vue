<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alx12qbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="alx12qbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bug" /></template>
