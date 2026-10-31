<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mopkyd0bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mopkyd0bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:headphones-16-solid" /></template>
