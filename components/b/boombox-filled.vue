<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1b_p5bbe.css';
import '../../css/o/ogqh4qb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1b_p5bbe"/><path class="ogqh4qb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:boombox-filled" /></template>
