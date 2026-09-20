<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plpwqubjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="plpwqubjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrow-alt-circle-up-solid" /></template>
