<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9im0cz5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9im0cz5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-q-filled" /></template>
