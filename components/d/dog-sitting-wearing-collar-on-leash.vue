<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3alpibud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u3alpibud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-sitting-wearing-collar-on-leash" /></template>
