<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq53nzb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fq53nzb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:dash" /></template>
