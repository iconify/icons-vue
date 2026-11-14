<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjpen32sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjpen32sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-add-02" /></template>
