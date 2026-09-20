<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js7g39buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js7g39buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-up" /></template>
