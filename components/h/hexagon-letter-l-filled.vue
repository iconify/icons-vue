<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xce-k95br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xce-k95br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-l-filled" /></template>
