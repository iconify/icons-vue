<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8mj4hq0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8mj4hq0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fish-bone-filled" /></template>
