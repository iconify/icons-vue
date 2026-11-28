<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c77mr0lli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c77mr0lli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:credit-card-clock" /></template>
