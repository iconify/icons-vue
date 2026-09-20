<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6vr9snca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6vr9snca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:friends-off" /></template>
