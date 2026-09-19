<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nopt0ba4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nopt0ba4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-up-right-02" /></template>
