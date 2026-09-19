<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mopulcbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mopulcbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:glove" /></template>
