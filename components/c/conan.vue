<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvu91_p7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvu91_p7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:conan" /></template>
