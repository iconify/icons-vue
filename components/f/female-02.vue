<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd66qbc5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd66qbc5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:female-02" /></template>
