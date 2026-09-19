<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1zm2n9fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="v1zm2n9fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:app-26" /></template>
