<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr5wco3zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fr5wco3zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:log-remove" /></template>
