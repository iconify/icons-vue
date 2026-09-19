<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbmlbccky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbmlbccky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:logout-02" /></template>
