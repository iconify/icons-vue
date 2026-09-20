<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9frtlbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9frtlbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:blizzards-1-natural-disasters-blizzards-snow-bold" /></template>
