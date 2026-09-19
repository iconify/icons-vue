<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8w3mfbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v8w3mfbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:facebook-fill-12" /></template>
