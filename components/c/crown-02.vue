<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6neaebfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6neaebfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:crown-02" /></template>
