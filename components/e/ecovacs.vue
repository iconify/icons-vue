<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6ig7kb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6ig7kb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ecovacs" /></template>
