<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbldn1bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gbldn1bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:hotel-bed-5-remix" /></template>
