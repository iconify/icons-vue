<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4-ii8gqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4-ii8gqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chess-bishop-filled" /></template>
