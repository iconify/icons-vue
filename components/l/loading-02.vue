<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4jgbu-ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4jgbu-ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:loading-02" /></template>
