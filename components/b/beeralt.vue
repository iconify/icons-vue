<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-8dv_bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="y-8dv_bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:beeralt" /></template>
