<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbh2wzl7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rbh2wzl7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-right-circle-solid" /></template>
