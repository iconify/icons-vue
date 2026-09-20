<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knvzufbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knvzufbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-x" /></template>
