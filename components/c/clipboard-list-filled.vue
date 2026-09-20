<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj-mazb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj-mazb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clipboard-list-filled" /></template>
