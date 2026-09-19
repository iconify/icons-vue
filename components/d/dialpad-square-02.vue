<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyy9geb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyy9geb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dialpad-square-02" /></template>
