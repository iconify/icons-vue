<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua2u0eb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ua2u0eb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:eye-small" /></template>
