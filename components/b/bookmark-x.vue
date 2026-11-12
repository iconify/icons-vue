<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io7dnibtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io7dnibtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-x" /></template>
