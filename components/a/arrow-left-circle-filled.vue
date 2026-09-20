<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm5s2311v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm5s2311v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-left-circle-filled" /></template>
