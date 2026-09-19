<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twi6k7b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="twi6k7b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-latin-small" /></template>
