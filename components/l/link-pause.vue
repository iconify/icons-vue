<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmn7gs-9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmn7gs-9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:link-pause" /></template>
